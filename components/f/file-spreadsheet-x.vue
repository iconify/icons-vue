<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnfh2xb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnfh2xb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-spreadsheet-x" /></template>
