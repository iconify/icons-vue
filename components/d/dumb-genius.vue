<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opo08-b2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="opo08-b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumb-genius" /></template>
