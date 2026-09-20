<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3i5_5bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w3i5_5bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:join-corner-arrow-3" /></template>
