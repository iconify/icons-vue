<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6l78ybxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u6l78ybxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:gift" /></template>
