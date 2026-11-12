<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgs5ujm3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fgs5ujm3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:journiv-dark" /></template>
