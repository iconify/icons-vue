<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inu9bub3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inu9bub3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bazarr" /></template>
