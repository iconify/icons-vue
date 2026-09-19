<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzc6dub2d.css';
import '../../css/f/f7ljz7b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xzc6dub2d"/><path class="f7ljz7b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:fish" /></template>
