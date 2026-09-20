<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvkz25b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path clip-rule="evenodd" class="nvkz25b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:calculator-alt" /></template>
