<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrvfdp9vf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrvfdp9vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:circle-3" /></template>
