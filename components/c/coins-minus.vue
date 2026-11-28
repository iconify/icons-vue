<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts3avnb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts3avnb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:coins-minus" /></template>
