<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_9vdtigo.css';
import '../../css/e/etu-42buw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x_9vdtigo"/><path class="etu-42buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:klipper" /></template>
