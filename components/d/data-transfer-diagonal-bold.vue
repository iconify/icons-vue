<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxf5o4ixa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxf5o4ixa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:data-transfer-diagonal-bold" /></template>
