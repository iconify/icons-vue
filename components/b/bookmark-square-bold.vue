<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8eri-m2c.css';
import '../../css/c/c2xn2qjho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h8eri-m2c"/><path class="c2xn2qjho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-square-bold" /></template>
