<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3ffuob8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3ffuob8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-search" /></template>
