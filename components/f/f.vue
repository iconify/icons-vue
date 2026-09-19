<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0qy6t9rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="q0qy6t9rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:f" /></template>
