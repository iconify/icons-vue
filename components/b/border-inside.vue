<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uww1vyvgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uww1vyvgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:border-inside" /></template>
