<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5p-wbcbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5p-wbcbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-bold-circle" /></template>
