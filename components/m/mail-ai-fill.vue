<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocmvvdv7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocmvvdv7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mail-ai-fill" /></template>
