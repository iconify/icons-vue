<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmc2g5_rg.css';
import '../../css/s/s5ck4pbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmc2g5_rg"/><path class="s5ck4pbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-shekel" /></template>
