<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmd0_6_fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dmd0_6_fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-question" /></template>
