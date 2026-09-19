<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dee6m-bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dee6m-bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:bookmark" /></template>
