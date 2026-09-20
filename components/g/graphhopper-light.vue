<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxxbg7bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fxxbg7bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:graphhopper-light" /></template>
