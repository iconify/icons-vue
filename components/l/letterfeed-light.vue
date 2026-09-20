<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp6fcs6dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zp6fcs6dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:letterfeed-light" /></template>
