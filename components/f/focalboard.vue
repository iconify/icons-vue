<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz8kk617p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bz8kk617p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:focalboard" /></template>
