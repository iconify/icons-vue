<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5r6o_bjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h5r6o_bjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:live-blog" /></template>
