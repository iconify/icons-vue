<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m25gomsvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m25gomsvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-xml-light" /></template>
