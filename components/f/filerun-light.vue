<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz_xj2mif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xz_xj2mif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filerun-light" /></template>
