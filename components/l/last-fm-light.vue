<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ows--s8kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ows--s8kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:last-fm-light" /></template>
