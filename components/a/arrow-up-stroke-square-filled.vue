<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc0z2hpjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc0z2hpjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-stroke-square-filled" /></template>
