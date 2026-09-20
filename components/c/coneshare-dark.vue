<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4x8skmmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i4x8skmmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:coneshare-dark" /></template>
