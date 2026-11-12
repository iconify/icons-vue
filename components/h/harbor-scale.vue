<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr-vtvbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nr-vtvbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:harbor-scale" /></template>
