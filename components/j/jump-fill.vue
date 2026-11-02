<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aviuuubzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aviuuubzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:jump-fill" /></template>
