<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6xaqqbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6xaqqbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cpu-sparkle-fill-round" /></template>
