<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc9h1nboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":750};
const content = `<path class="jc9h1nboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:envelope" /></template>
