<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqr0zm-hq.css';
import '../../css/n/n2x5xwbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bqr0zm-hq"/><path class="n2x5xwbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dosvault-light" /></template>
