<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn0zbtb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xn0zbtb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cellular-network-5g-solid" /></template>
