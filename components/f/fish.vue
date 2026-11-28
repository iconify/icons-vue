<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgrl7lbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgrl7lbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:fish" /></template>
