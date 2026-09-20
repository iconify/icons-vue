<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njnmu2p-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="njnmu2p-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-arrows-right" /></template>
