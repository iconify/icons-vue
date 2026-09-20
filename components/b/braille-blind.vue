<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elx6aybyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="elx6aybyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:braille-blind" /></template>
