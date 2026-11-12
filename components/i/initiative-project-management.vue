<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u01w8rbik.css';
import '../../css/m/m5ihdsbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u01w8rbik"/><path class="m5ihdsbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:initiative-project-management" /></template>
