<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hazr2xbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hazr2xbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:garage-dark" /></template>
