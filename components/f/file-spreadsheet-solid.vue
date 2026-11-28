<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9ddq9bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9ddq9bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-spreadsheet-solid" /></template>
