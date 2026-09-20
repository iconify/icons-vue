<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbp_debio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbp_debio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:inspect-line" /></template>
