<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyqt350ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tyqt350ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:geopulse-dark" /></template>
