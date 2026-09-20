<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq4_tk9zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tq4_tk9zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:home-1-flat" /></template>
