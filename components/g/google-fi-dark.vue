<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq1hv3m9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nq1hv3m9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-fi-dark" /></template>
