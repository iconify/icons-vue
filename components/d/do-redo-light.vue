<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2cebccoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2cebccoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:do-redo-light" /></template>
