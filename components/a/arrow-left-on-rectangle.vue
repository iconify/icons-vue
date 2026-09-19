<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxjktu_0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxjktu_0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-left-on-rectangle" /></template>
