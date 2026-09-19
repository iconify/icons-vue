<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol1j8y3wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ol1j8y3wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:chart-area" /></template>
