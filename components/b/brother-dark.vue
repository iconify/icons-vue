<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i112icc0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i112icc0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:brother-dark" /></template>
