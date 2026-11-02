<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r78mxnwkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r78mxnwkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-1-line" /></template>
