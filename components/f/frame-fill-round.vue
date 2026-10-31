<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru2dtsixs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru2dtsixs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:frame-fill-round" /></template>
