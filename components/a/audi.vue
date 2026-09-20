<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xky_hh0hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xky_hh0hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:audi" /></template>
