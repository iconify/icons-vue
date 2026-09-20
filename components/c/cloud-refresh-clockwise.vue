<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro5b2tlle.css';
import '../../css/f/f-vbie9xr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro5b2tlle"/><path class="f-vbie9xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cloud-refresh-clockwise" /></template>
