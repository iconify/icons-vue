<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqzm3-bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqzm3-bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-fill" /></template>
