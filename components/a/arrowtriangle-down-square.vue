<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk6_68bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xk6_68bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowtriangle-down-square" /></template>
