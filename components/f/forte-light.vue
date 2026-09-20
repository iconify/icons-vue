<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wak_5j_yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wak_5j_yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:forte-light" /></template>
