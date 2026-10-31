<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx73u_ukv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx73u_ukv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-upload-round" /></template>
