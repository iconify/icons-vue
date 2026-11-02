<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj8cz3zgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj8cz3zgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hamburger-line" /></template>
