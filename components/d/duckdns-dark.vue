<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxhh4rbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cxhh4rbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:duckdns-dark" /></template>
