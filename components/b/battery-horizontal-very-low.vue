<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc37nr-lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xc37nr-lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:battery-horizontal-very-low" /></template>
