<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud9xtmhvv.css';
import '../../css/m/mxpx1okuh.css';
import '../../css/w/w_fsjlwse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ud9xtmhvv"/><path class="mxpx1okuh"/><path class="w_fsjlwse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:aok" /></template>
