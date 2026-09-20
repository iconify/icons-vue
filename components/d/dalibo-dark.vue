<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh45i_bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wh45i_bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dalibo-dark" /></template>
