<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5izahbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w5izahbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:caret-right" /></template>
