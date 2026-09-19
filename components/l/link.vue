<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuipojbnc.css';
import '../../css/m/mxlj29bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nuipojbnc"/><path class="mxlj29bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:link" /></template>
