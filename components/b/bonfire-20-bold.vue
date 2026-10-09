<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcv9toj4y.css';
import '../../css/t/tgkamedfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jcv9toj4y"/><path class="tgkamedfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bonfire-20-bold" /></template>
