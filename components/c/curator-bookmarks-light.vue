<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgkp2kb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fgkp2kb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:curator-bookmarks-light" /></template>
