<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsfm2oczx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dsfm2oczx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:azirevpn-light" /></template>
