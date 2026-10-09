<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0t5o3l-d.css';
import '../../css/k/k4k55lxkj.css';
import '../../css/v/vl7jw2b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f0t5o3l-d"/><path class="k4k55lxkj"/><path class="vl7jw2b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cube-20" /></template>
