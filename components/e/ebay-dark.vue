<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tabtax0oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tabtax0oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ebay-dark" /></template>
