<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_ij37bly.css';
import '../../css/c/c3p_xw4dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_ij37bly"/><path class="c3p_xw4dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:acquiremock-dark" /></template>
