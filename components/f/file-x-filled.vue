<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf44ky2lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf44ky2lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-x-filled" /></template>
