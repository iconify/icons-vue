<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4tu03bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="u4tu03bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-check-fill" /></template>
