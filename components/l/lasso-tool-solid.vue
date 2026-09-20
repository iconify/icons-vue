<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj47kcbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lj47kcbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:lasso-tool-solid" /></template>
