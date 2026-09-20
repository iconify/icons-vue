<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki7-1hdyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki7-1hdyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:close-small-fill" /></template>
