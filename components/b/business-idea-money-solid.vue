<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggq3csbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ggq3csbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:business-idea-money-solid" /></template>
