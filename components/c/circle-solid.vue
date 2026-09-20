<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9fcafbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="f9fcafbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:circle-solid" /></template>
