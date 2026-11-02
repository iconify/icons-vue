<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh-1z2bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh-1z2bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:line-fill" /></template>
