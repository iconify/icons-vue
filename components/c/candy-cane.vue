<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh5wxqbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vh5wxqbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:candy-cane" /></template>
