<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab5x98fnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab5x98fnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drawer-2-fill" /></template>
