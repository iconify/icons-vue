<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g64y_l5-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g64y_l5-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:immich-frame-light" /></template>
