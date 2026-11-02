<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtb85pbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtb85pbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chopsticks-fill" /></template>
