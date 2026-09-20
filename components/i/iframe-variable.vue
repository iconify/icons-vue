<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz90e-imq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz90e-imq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:iframe-variable" /></template>
