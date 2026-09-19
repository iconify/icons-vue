<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psxhry76x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="psxhry76x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:file-document-fill" /></template>
