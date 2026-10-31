<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1rmxw4ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1rmxw4ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-1-fill-round" /></template>
