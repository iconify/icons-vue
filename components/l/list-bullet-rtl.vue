<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rif1eh3zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rif1eh3zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:list-bullet-rtl" /></template>
