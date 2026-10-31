<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkubfebqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkubfebqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-right-down-duotone-round" /></template>
