<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suh-k03fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="suh-k03fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-document-fill-12" /></template>
