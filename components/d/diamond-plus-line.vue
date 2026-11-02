<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_8v1sbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_8v1sbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:diamond-plus-line" /></template>
