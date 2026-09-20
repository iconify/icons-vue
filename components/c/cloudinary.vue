<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvq-k4bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dvq-k4bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cloudinary" /></template>
