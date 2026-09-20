<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_tdqfbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_tdqfbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:driver2-filled" /></template>
