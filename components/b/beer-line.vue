<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct2qukgch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct2qukgch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:beer-line" /></template>
