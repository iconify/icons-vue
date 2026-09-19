<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i219wytpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i219wytpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:cloud-upload" /></template>
