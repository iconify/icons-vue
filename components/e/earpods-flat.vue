<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8jx-wbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t8jx-wbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:earpods-flat" /></template>
