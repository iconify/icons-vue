<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw_eb9b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uw_eb9b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gopeed-light" /></template>
