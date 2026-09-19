<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kko_rr_sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kko_rr_sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:language" /></template>
