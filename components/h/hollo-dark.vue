<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf0zp_bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bf0zp_bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hollo-dark" /></template>
