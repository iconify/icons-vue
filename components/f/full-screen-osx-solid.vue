<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so70jzd9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="so70jzd9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:full-screen-osx-solid" /></template>
