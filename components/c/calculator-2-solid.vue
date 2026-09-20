<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdlrvj-pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xdlrvj-pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:calculator-2-solid" /></template>
