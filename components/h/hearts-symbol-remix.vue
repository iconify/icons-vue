<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urk_3ebrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="urk_3ebrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hearts-symbol-remix" /></template>
