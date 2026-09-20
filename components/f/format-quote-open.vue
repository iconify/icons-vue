<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpnnjfyzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpnnjfyzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-quote-open" /></template>
