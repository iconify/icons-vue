<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyg0w2hhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyg0w2hhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dlthub" /></template>
