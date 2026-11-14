<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj_h01bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj_h01bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:add-square" /></template>
