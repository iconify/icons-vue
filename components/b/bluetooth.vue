<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkwz5233h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xkwz5233h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:bluetooth" /></template>
