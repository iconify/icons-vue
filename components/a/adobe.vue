<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/are8-xb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="are8-xb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:adobe" /></template>
