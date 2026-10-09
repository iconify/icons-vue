<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aem9n2zvr.css';
import '../../css/w/wqxi-7byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aem9n2zvr"/><path class="wqxi-7byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-combo-20" /></template>
