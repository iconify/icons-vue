<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6w8sub2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6w8sub2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:cage" /></template>
