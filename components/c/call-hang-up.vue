<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv1-teoia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="fv1-teoia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:call-hang-up" /></template>
