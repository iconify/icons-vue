<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf_1mybtb.css';
import '../../css/r/r2pseab2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sf_1mybtb"/><path class="r2pseab2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fluidd" /></template>
