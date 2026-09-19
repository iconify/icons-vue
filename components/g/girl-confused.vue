<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq9p_gbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dq9p_gbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:girl-confused" /></template>
