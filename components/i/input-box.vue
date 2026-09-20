<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy80e3meu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="sy80e3meu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:input-box" /></template>
