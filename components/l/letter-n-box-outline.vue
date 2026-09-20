<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr08k9b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr08k9b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-n-box-outline" /></template>
