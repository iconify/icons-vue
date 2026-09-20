<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhh38hbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhh38hbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dip-switch" /></template>
