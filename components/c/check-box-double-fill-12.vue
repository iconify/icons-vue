<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5sn11bpb.css';
import '../../css/w/w6kke-lrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="i5sn11bpb"/><path class="w6kke-lrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-box-double-fill-12" /></template>
