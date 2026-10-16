<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjljwei0o.css';
import '../../css/g/ghw7-wbwc.css';
import '../../css/b/b_vy63bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cjljwei0o"/><path class="ghw7-wbwc"/><path class="b_vy63bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:brick-wall-20-bold" /></template>
