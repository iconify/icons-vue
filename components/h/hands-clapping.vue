<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjskp-bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="gjskp-bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hands-clapping" /></template>
