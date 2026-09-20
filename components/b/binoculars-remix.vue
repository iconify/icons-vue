<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke7fh00we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ke7fh00we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:binoculars-remix" /></template>
