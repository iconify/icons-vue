<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do2_lcsjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="do2_lcsjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:affine-dark" /></template>
