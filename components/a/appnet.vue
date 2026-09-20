<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7xb_hkno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7xb_hkno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:appnet" /></template>
