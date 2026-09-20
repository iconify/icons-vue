<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi8ammb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wi8ammb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-ads-logo-solid" /></template>
