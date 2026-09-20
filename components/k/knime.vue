<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so21iw-ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so21iw-ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:knime" /></template>
