<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q84-m7bmy.css';
import '../../css/z/zr8ct4-nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q84-m7bmy"/><path class="zr8ct4-nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:homeassistant" /></template>
