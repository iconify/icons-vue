<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsb2-hb_n.css';
import '../../css/r/r56804bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zsb2-hb_n"/><path class="r56804bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ladder-20-bold" /></template>
