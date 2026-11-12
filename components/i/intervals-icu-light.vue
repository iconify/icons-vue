<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shcs-1hry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="shcs-1hry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:intervals-icu-light" /></template>
