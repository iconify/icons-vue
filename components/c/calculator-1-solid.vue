<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by-5y11mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="by-5y11mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:calculator-1-solid" /></template>
