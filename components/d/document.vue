<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxxquib2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nxxquib2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:document" /></template>
