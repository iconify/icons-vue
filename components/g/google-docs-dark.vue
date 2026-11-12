<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxk51mbgs.css';
import '../../css/p/p2k-rbb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oxk51mbgs"/><path class="p2k-rbb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-docs-dark" /></template>
