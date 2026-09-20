<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocltiu-dk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ocltiu-dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cellular-network-4g" /></template>
