<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv0x2jbvr.css';
import '../../css/x/xsuq0vbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fv0x2jbvr"/><path class="xsuq0vbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lingva-translate-dark" /></template>
