<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij621sbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ij621sbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:haptic-light" /></template>
