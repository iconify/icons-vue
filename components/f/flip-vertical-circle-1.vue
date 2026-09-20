<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pis88xbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="pis88xbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flip-vertical-circle-1" /></template>
