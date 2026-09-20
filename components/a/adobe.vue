<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggb5l7bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ggb5l7bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe" /></template>
