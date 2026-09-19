<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5_sp-b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="j5_sp-b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:balance-scale" /></template>
