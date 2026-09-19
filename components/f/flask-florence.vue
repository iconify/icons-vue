<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0kp65hhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x0kp65hhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:flask-florence" /></template>
