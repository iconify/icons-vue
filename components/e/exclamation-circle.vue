<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzqv24bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mzqv24bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:exclamation-circle" /></template>
