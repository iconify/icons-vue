<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6xfb8lhn.css';
import '../../css/t/tiltjra3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u6xfb8lhn"/><path class="tiltjra3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:geeftlist-dark" /></template>
