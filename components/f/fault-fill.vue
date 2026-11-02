<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tscstsbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tscstsbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fault-fill" /></template>
