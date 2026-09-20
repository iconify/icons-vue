<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxpn3x-hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxpn3x-hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:auchan" /></template>
