<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycxe1lb0r.css';
import '../../css/e/eohaobbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ycxe1lb0r"/><path class="eohaobbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ear-20" /></template>
