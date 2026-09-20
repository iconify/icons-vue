<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4h_36bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4h_36bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-lock-outline" /></template>
