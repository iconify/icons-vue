<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgzard9se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgzard9se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:entrance-line" /></template>
