<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2cwtf82h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h2cwtf82h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:countly-dark" /></template>
