<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/netg96bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="netg96bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:labview" /></template>
