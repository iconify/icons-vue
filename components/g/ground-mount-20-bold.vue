<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkqr1j59e.css';
import '../../css/g/gx519cbvi.css';
import '../../css/y/yv842m9yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rkqr1j59e"/><path class="gx519cbvi"/><path class="yv842m9yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ground-mount-20-bold" /></template>
