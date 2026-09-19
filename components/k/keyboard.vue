<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dia0nqdkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dia0nqdkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:keyboard" /></template>
