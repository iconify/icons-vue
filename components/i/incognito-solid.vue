<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0a_tmbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0a_tmbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:incognito-solid" /></template>
