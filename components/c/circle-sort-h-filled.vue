<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybni8x36i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ybni8x36i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-sort-h-filled" /></template>
