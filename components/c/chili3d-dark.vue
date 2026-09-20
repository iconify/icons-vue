<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3xd-ebwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u3xd-ebwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chili3d-dark" /></template>
