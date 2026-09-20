<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5skxtb6n.css';
import '../../css/n/njarltr6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t5skxtb6n"/><path class="njarltr6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:log-in-rtl" /></template>
