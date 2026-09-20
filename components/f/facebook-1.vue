<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9j72lbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w9j72lbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:facebook-1" /></template>
