<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxhz6yb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxhz6yb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:award" /></template>
