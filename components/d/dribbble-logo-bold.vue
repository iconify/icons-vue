<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2ffzrbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2ffzrbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:dribbble-logo-bold" /></template>
