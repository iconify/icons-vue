<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlop-v64y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tlop-v64y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:contao-dark" /></template>
