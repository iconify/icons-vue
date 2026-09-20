<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yveffblrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yveffblrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-code-outline" /></template>
