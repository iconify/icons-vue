<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj-jz8bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xj-jz8bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:login-1-remix" /></template>
