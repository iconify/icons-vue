<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp5wc9bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cp5wc9bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:input-box-solid" /></template>
