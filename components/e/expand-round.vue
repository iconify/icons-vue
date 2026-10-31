<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i74gyzbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i74gyzbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:expand-round" /></template>
