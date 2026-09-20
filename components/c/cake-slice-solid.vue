<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyz19x35s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gyz19x35s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cake-slice-solid" /></template>
