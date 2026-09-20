<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_lw8vxzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c_lw8vxzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:magic-wand-1-remix" /></template>
