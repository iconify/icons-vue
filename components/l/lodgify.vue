<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzmyd9baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="yzmyd9baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:lodgify" /></template>
