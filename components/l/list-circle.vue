<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv6rri-bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nv6rri-bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:list-circle" /></template>
