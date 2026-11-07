<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe050eb3u.css';
import '../../css/x/x8k8-5b4d.css';
import '../../css/z/zw138qb4j.css';
import '../../css/v/vbpdh7-jd.css';
import '../../css/r/ri-4y14ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe050eb3u"/><path class="x8k8-5b4d"/><path class="zw138qb4j"/><path class="vbpdh7-jd"/><path class="ri-4y14ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magic-wand-3-bold" /></template>
