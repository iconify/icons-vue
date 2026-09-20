<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffx3t1d0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ffx3t1d0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-prime-light" /></template>
