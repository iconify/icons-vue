<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf8xf_biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf8xf_biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:coder" /></template>
