<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diga86qzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="diga86qzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:corner-down-left-fill" /></template>
