<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1sv1_bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v1sv1_bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-premiere-pro-dark" /></template>
