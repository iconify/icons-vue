<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcpfxpp0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wcpfxpp0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bitcoin-dark" /></template>
