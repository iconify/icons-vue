<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlaay_4cm.css';
import '../../css/f/f4g0gcbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wlaay_4cm"/><path class="f4g0gcbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lock-20-bold" /></template>
