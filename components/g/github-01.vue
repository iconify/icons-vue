<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jizyhl_ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jizyhl_ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:github-01" /></template>
