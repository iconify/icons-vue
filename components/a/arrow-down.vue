<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roo_fduln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="roo_fduln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:arrow-down" /></template>
