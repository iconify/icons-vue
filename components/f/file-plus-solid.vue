<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcw1qbpct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcw1qbpct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-plus-solid" /></template>
