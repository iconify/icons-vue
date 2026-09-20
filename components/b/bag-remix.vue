<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3f_7bcue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v3f_7bcue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:bag-remix" /></template>
