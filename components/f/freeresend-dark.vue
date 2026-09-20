<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p90yc2h1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p90yc2h1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freeresend-dark" /></template>
