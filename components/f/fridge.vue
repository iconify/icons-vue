<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg7s1p4af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg7s1p4af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:fridge" /></template>
