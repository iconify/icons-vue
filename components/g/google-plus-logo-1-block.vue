<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvpxvwbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pvpxvwbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-plus-logo-1-block" /></template>
