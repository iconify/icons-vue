<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/varmcvqqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="varmcvqqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:assembly-att" /></template>
