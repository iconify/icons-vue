<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmc55qbpv.css';
import '../../css/g/g5l3qyt-f.css';
import '../../css/w/wlqkezb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mmc55qbpv"/><circle class="g5l3qyt-f"/><circle class="wlqkezb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:global-threat-map-light" /></template>
