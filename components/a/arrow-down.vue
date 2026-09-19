<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neyc37j5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="neyc37j5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-down" /></template>
