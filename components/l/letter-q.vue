<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw72_ccft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw72_ccft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-q" /></template>
