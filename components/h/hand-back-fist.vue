<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq82k4bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="rq82k4bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-back-fist" /></template>
