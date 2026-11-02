<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4-3v1vys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4-3v1vys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-5-fill" /></template>
