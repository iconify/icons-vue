<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr9vhtbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mr9vhtbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:insert-center-left-1" /></template>
