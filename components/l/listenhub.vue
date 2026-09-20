<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf1vx18wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf1vx18wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:listenhub" /></template>
