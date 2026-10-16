<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlf07hbzj.css';
import '../../css/w/w9mp4gb4o.css';
import '../../css/w/we5ze0blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qlf07hbzj"/><path class="w9mp4gb4o"/><path class="we5ze0blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:brick-wall-20" /></template>
