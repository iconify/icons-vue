<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w71h-cbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w71h-cbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:battery-low" /></template>
