<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ego17gzid.css';
import '../../css/g/gx13bbcrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ego17gzid"/><path class="gx13bbcrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:etherpad-dark" /></template>
