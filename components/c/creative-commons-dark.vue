<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh-vg0nom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qh-vg0nom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:creative-commons-dark" /></template>
