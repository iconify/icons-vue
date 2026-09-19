<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkwhx1bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkwhx1bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:frame" /></template>
