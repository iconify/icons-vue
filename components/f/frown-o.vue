<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d19cyfgoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d19cyfgoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:frown-o" /></template>
