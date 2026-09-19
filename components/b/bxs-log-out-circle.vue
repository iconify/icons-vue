<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waa9zhbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waa9zhbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-log-out-circle" /></template>
