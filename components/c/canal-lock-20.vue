<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0ni6vb5b.css';
import '../../css/w/wl476na-m.css';
import '../../css/r/riruf7bad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g0ni6vb5b"/><path class="wl476na-m"/><path class="riruf7bad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:canal-lock-20" /></template>
