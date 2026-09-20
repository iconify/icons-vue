<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxiza7bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxiza7bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-big-left" /></template>
