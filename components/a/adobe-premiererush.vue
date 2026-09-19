<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cntpq-7ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="cntpq-7ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:adobe-premiererush" /></template>
