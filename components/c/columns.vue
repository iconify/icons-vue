<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyd2yshmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyd2yshmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:columns" /></template>
