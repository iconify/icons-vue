<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyymi3ddh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xyymi3ddh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:attribution-solid" /></template>
