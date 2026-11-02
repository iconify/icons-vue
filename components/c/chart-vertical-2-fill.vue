<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb5w3nb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb5w3nb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-vertical-2-fill" /></template>
