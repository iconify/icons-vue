<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyp7umbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xyp7umbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bludit-light" /></template>
