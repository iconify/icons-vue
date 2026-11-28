<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlfrt5x2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlfrt5x2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hand-coin" /></template>
