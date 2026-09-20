<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u563jbcsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u563jbcsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cloud-mist-2-bold" /></template>
