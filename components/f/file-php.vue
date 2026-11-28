<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dga23pugb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dga23pugb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-php" /></template>
