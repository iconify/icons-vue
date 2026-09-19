<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmqpj0ysb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="lmqpj0ysb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:caret-square-left" /></template>
