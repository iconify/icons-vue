<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzjxjac2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzjxjac2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:building-1-line" /></template>
