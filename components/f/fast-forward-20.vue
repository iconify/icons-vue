<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-7yzwbmb.css';
import '../../css/n/n0tshoxcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a-7yzwbmb"/><path class="n0tshoxcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fast-forward-20" /></template>
