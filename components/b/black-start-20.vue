<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orlk51biu.css';
import '../../css/t/tjdhhwbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="orlk51biu"/><path class="tjdhhwbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:black-start-20" /></template>
