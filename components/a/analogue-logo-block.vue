<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okvmcsb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="okvmcsb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:analogue-logo-block" /></template>
