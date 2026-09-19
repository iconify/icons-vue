<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt3masb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yt3masb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:geo-location-24px" /></template>
