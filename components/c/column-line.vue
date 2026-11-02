<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqtmb4byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqtmb4byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:column-line" /></template>
