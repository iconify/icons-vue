<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo9kjdz5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo9kjdz5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bread-fill" /></template>
