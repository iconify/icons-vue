<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9c5oyb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="c9c5oyb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:button-power-1" /></template>
