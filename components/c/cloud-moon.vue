<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcraqe0wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="qcraqe0wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cloud-moon" /></template>
