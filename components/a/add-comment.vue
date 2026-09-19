<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6geo1bkk.css';
import '../../css/t/t_6ep1b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h6geo1bkk"/><path class="t_6ep1b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:add-comment" /></template>
