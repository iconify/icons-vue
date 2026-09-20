<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkbu03bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkbu03bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ebike-line" /></template>
