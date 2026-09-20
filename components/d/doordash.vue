<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo5zol14h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oo5zol14h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:doordash" /></template>
