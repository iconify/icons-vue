<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlcb74b2i.css';
import '../../css/n/nlxy_dbcm.css';
import '../../css/m/moq4ohbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xlcb74b2i"/><path class="nlxy_dbcm"/><path class="moq4ohbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kometa" /></template>
