<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwnecvwyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bwnecvwyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:devicon-wordmark" /></template>
