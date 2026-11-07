<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgx80dbgw.css';
import '../../css/s/sf0e3noev.css';
import '../../css/z/zmpjdkihd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgx80dbgw"/><path clip-rule="evenodd" class="sf0e3noev"/><path clip-rule="evenodd" class="zmpjdkihd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dropper-minimalistic-2-outline" /></template>
