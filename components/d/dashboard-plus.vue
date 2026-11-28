<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx-p57btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx-p57btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:dashboard-plus" /></template>
