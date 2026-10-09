<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptysfhbch.css';
import '../../css/g/ge6al85qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ptysfhbch"/><path class="ge6al85qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:euro-20-bold" /></template>
