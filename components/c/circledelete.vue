<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxg55ebbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="uxg55ebbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circledelete" /></template>
