<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u60jawbmr.css';
import '../../css/e/etvlrmq6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="u60jawbmr"/><path class="etvlrmq6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbassets" /></template>
