<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px9-5bcch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px9-5bcch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:line-height-fill" /></template>
