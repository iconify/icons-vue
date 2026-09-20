<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv4k8x9qx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv4k8x9qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:encryption-remove-outline" /></template>
