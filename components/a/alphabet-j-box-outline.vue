<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npe-89b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npe-89b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-j-box-outline" /></template>
