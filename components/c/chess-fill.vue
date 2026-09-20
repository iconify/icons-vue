<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prisdxbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prisdxbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chess-fill" /></template>
