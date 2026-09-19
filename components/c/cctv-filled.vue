<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7rcn_r6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7rcn_r6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cctv-filled" /></template>
