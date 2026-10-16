<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co0vf9bvy.css';
import '../../css/y/y91t96b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="co0vf9bvy"/><path class="y91t96b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:aspect-ratio-20" /></template>
