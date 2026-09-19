<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnfpavb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="bnfpavb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-upload" /></template>
