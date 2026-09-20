<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esyxanb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="esyxanb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:document-2-outline" /></template>
