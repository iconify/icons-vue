<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gav8xkmpk.css';
import '../../css/s/sux_alb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gav8xkmpk"/><path class="sux_alb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:burger-20" /></template>
