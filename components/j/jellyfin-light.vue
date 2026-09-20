<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe2dg1bnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pe2dg1bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jellyfin-light" /></template>
