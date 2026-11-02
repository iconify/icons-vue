<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e10ivmb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e10ivmb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dogecoin-doge-line" /></template>
