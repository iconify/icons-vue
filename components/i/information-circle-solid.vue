<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du3luob1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="du3luob1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:information-circle-solid" /></template>
