<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo6-9db7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jo6-9db7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:backpack-solid" /></template>
