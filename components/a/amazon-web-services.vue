<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzbwajvnv.css';
import '../../css/f/fg1jarbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dzbwajvnv"/><path class="fg1jarbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-web-services" /></template>
