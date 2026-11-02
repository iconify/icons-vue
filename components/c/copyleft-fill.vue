<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abb396d2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abb396d2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copyleft-fill" /></template>
