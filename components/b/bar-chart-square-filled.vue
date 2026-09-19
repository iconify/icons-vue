<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiddfub6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jiddfub6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bar-chart-square-filled" /></template>
