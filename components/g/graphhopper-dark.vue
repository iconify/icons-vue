<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snv2imbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="snv2imbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:graphhopper-dark" /></template>
