<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqs7bev6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mqs7bev6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linkding-dark" /></template>
