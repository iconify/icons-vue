<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjv4p1bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjv4p1bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mail-plus" /></template>
