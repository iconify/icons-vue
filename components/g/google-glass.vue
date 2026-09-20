<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwbtljbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwbtljbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:google-glass" /></template>
