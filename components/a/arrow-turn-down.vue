<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zanalnayr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="zanalnayr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-turn-down" /></template>
