<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbva30-wv.css';
import '../../css/h/hs2nkdwup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xbva30-wv"/><path class="hs2nkdwup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-ambulance-car" /></template>
