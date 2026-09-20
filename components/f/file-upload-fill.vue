<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq5o52bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq5o52bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:file-upload-fill" /></template>
