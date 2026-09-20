<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7u2mac0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7u2mac0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-down-line" /></template>
