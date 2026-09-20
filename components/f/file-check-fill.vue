<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvhu42n8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvhu42n8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-check-fill" /></template>
