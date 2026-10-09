<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqtu52b6d.css';
import '../../css/k/k0ztijb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aqtu52b6d"/><path class="k0ztijb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-island-20" /></template>
