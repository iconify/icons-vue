<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls0it7-zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ls0it7-zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:croisant" /></template>
