<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhrvvgbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mhrvvgbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:letter-opened-outline" /></template>
