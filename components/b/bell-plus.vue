<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reywt300r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="reywt300r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bell-plus" /></template>
