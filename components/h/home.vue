<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z22_sqa8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z22_sqa8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:home" /></template>
