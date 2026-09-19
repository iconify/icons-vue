<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4vt97b1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="u4vt97b1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowtriangle-right-square" /></template>
