<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctkrq_x0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ctkrq_x0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:button-fast-forward-2-remix" /></template>
