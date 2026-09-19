<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etzt6g6pq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="etzt6g6pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:groovy" /></template>
