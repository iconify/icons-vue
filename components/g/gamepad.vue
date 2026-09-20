<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy3p889il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="yy3p889il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:gamepad" /></template>
