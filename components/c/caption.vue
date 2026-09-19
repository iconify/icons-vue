<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj_ko-1ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj_ko-1ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:caption" /></template>
