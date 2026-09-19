<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw7tdp1nv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw7tdp1nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-remote" /></template>
