<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev1riup_j.css';
import '../../css/h/hufvzydwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ev1riup_j"/><path class="hufvzydwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:atlas-network-dark" /></template>
