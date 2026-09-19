<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pou3q3wuy.css';
import '../../css/v/vj_fb8bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pou3q3wuy"/><path class="vj_fb8bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:home-circle" /></template>
