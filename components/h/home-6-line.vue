<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfoxkd_6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfoxkd_6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-6-line" /></template>
