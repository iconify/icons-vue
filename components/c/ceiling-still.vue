<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt04fab_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt04fab_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-still" /></template>
