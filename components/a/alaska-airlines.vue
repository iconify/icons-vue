<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz401zx2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wz401zx2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alaska-airlines" /></template>
