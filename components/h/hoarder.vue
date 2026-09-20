<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiv-uob8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wiv-uob8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hoarder" /></template>
