<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_nn7bcfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f_nn7bcfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:delete-tag-solid" /></template>
