<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bji23jdtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="bji23jdtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:globe-alt" /></template>
