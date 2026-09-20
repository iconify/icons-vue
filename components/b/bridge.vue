<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsx_xhbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsx_xhbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bridge" /></template>
