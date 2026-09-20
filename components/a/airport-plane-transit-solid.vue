<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz58s7yxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xz58s7yxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:airport-plane-transit-solid" /></template>
