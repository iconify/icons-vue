<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oobjjsbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oobjjsbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coffee-round" /></template>
