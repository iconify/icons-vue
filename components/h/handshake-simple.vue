<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr-rl2bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hr-rl2bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:handshake-simple" /></template>
