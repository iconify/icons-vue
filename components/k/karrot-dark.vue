<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrwutubbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wrwutubbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:karrot-dark" /></template>
