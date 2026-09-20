<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxkiydbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2555,"height":810};
const content = `<path class="dxkiydbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hancom" /></template>
