<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9o6lfw2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="c9o6lfw2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:align-center" /></template>
