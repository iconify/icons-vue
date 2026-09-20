<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm24ldb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rm24ldb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:bell-solid" /></template>
