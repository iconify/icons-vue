<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of3k1s7ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="of3k1s7ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:arrow-previous-rtl" /></template>
