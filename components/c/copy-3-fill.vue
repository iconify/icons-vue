<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4xb5-tlu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4xb5-tlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copy-3-fill" /></template>
