<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t83_2skig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t83_2skig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bell-stroke-20" /></template>
