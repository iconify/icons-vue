<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjccp8b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mjccp8b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:airport-plane-flat" /></template>
