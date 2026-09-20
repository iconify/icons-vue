<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqhz4jlvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqhz4jlvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bank" /></template>
