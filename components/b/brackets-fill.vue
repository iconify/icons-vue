<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufqns12ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufqns12ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brackets-fill" /></template>
