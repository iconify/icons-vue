<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lycl2fbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lycl2fbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:goblet-square-full" /></template>
