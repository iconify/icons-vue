<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra_mhhb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ra_mhhb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:fastforward-clock-remix" /></template>
