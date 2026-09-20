<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddx_pdqze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddx_pdqze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bank-transfer" /></template>
