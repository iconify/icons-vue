<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8-cvpb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a8-cvpb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:browser-dashboard-solid" /></template>
