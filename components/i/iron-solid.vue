<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql-w3z2ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ql-w3z2ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:iron-solid" /></template>
