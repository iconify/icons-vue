<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngkp_tt1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ngkp_tt1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-lightroom-light" /></template>
