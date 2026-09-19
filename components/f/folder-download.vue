<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am802ybiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am802ybiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:folder-download" /></template>
