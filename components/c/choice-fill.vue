<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jie5d7b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jie5d7b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:choice-fill" /></template>
