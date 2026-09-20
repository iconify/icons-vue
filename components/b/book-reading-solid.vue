<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amkv8ubhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="amkv8ubhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:book-reading-solid" /></template>
