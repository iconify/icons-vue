<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3f6luboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3f6luboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-key" /></template>
