<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxudpdy1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gxudpdy1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:krusader-light" /></template>
