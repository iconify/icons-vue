<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvn5oaboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nvn5oaboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:flow-chart-hierachy-bold" /></template>
