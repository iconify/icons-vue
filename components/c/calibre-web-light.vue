<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmw1q3zex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wmw1q3zex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:calibre-web-light" /></template>
