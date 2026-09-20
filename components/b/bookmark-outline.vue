<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5boeacaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n5boeacaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bookmark-outline" /></template>
