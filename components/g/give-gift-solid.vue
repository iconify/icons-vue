<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcw8lebxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcw8lebxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:give-gift-solid" /></template>
