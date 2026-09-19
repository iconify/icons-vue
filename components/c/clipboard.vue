<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtv-ejb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="jtv-ejb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:clipboard" /></template>
