<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kin1cxb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kin1cxb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:door-x" /></template>
