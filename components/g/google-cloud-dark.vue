<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obtzdzkzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="obtzdzkzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-cloud-dark" /></template>
