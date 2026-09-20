<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2_z2v3wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c2_z2v3wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:forward-end-circle" /></template>
