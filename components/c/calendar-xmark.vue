<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgeig3s5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qgeig3s5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:calendar-xmark" /></template>
