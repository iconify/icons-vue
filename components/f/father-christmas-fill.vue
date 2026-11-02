<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p206_1bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p206_1bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:father-christmas-fill" /></template>
