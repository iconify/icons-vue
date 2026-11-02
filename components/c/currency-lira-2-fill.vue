<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyue2kdmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyue2kdmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-lira-2-fill" /></template>
