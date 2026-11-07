<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkai44buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkai44buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:case-round-minimalistic-bold" /></template>
