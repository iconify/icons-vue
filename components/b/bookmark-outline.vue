<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0o3vwkfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k0o3vwkfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bookmark-outline" /></template>
