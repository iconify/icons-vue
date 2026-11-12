<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nim0ecb_g.css';
import '../../css/u/uio7vmi8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nim0ecb_g"/><path class="uio7vmi8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-messages-dark" /></template>
