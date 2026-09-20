<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szu8u-bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="szu8u-bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-round-right-flat" /></template>
