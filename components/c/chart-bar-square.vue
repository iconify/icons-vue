<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7103_b_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="w7103_b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chart-bar-square" /></template>
