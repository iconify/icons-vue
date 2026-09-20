<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmxnrm70b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmxnrm70b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:label" /></template>
