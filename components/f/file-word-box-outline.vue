<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xattt94_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xattt94_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-word-box-outline" /></template>
