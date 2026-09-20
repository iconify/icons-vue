<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncs3bccmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncs3bccmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hexagon-slice-6" /></template>
