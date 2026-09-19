<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvg12-bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yvg12-bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bold-fill-12" /></template>
