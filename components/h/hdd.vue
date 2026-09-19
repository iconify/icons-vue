<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmg_qxorr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="vmg_qxorr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:hdd" /></template>
