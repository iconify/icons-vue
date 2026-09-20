<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv16s7lvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv16s7lvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:candy-round-1" /></template>
