<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmg_78b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmg_78b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cannabis-off-fill" /></template>
