<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0afn-ovm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z0afn-ovm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dhl-light" /></template>
