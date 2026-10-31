<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnia0x62t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnia0x62t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bone-fill-round" /></template>
