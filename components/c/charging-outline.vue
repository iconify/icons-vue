<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo56a125d.css';
import '../../css/j/je4d_rxfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo56a125d"/><path class="je4d_rxfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:charging-outline" /></template>
