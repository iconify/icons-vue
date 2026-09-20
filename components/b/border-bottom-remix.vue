<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1shg7kbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m1shg7kbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:border-bottom-remix" /></template>
