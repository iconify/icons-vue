<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgyjh9bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="tgyjh9bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:joint" /></template>
