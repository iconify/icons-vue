<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_d_7ztlb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o_d_7ztlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cane-alt" /></template>
