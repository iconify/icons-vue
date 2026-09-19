<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3qf5l6ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j3qf5l6ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-down-circle" /></template>
