<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3w52bb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d3w52bb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-photos-light" /></template>
