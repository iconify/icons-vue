<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkrxvcc8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rkrxvcc8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-analytics-light" /></template>
