<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5g2j3bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5g2j3bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-table-box-outline" /></template>
