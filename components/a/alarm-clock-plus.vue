<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdbst15to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdbst15to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:alarm-clock-plus" /></template>
