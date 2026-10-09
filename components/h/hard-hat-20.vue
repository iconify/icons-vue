<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4yi2x4py.css';
import '../../css/u/uax5j8b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z4yi2x4py"/><path class="uax5j8b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hard-hat-20" /></template>
