<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki73m08oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ki73m08oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:inspection-panel-filled" /></template>
