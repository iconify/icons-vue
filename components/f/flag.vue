<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv8if_ohd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uv8if_ohd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:flag" /></template>
