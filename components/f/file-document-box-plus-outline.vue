<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw0saubfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw0saubfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-document-box-plus-outline" /></template>
