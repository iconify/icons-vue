<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clkrv286q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clkrv286q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cupcake" /></template>
