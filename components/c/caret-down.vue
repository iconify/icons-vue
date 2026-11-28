<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh51pmbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh51pmbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:caret-down" /></template>
