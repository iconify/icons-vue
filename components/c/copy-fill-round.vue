<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e62t-5brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e62t-5brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-fill-round" /></template>
