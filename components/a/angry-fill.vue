<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0361ybcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0361ybcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:angry-fill" /></template>
