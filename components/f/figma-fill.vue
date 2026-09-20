<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5izz9dil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j5izz9dil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:figma-fill" /></template>
