<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqx-rabmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xqx-rabmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:calculator-20-solid" /></template>
