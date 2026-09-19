<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g66jyg1bm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g66jyg1bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:atm" /></template>
