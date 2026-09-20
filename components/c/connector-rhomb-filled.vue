<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_dhl2b5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d_dhl2b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:connector-rhomb-filled" /></template>
