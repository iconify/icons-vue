<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vszunpbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vszunpbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hops" /></template>
