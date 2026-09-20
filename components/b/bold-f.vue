<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcv1sbczx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lcv1sbczx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bold-f" /></template>
