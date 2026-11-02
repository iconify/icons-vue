<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wig5fjbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wig5fjbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:logs-fill" /></template>
