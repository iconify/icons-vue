<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg84oub9d.css';
import '../../css/u/udvwo6blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mg84oub9d"/><path clip-rule="evenodd" class="udvwo6blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:anja-solid" /></template>
