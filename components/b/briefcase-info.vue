<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt0ef04zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lt0ef04zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:briefcase-info" /></template>
