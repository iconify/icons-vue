<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfm6v04ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfm6v04ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-check-multiple" /></template>
