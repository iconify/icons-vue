<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtse33bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xtse33bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:listmonk" /></template>
