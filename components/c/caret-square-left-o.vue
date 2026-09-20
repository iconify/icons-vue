<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cflr1ab0i.css';
import '../../css/u/uxoqws25i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cflr1ab0i"/><path class="uxoqws25i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:caret-square-left-o" /></template>
