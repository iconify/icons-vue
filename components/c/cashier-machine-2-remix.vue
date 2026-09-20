<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz5y4by4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wz5y4by4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:cashier-machine-2-remix" /></template>
