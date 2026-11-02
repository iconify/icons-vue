<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3lzm8ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3lzm8ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:glass-cup-fill" /></template>
