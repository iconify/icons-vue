<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyz4uac8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jyz4uac8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:check-square-solid" /></template>
