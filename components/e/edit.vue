<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7gd7dfck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="q7gd7dfck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:edit" /></template>
