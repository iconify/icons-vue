<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi44x2b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hi44x2b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:code-scan" /></template>
