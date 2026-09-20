<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex2baqp8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ex2baqp8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-euro-fill" /></template>
