<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kngeejbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kngeejbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:feather-pen-solid" /></template>
