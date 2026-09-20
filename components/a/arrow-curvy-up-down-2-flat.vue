<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwn4e46yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fwn4e46yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-curvy-up-down-2-flat" /></template>
