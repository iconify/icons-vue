<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp9sllmfa.css';
import '../../css/q/qoo-_6bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp9sllmfa"/><path class="qoo-_6bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:business-product-supplier-1" /></template>
