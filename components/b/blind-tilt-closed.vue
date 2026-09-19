<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z33gtxdmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z33gtxdmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:blind-tilt-closed" /></template>
