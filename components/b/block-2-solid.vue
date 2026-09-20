<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1u09r4ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d1u09r4ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:block-2-solid" /></template>
