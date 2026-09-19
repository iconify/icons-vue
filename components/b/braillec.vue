<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0rrt-0dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="h0rrt-0dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:braillec" /></template>
