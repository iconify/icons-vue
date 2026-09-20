<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbi57gbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wbi57gbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:archive-box-solid" /></template>
