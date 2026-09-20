<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7ng3y57a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w7ng3y57a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:add-1" /></template>
