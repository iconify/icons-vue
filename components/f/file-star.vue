<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8ved5nop.css';
import '../../css/s/s5d7qab8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8ved5nop"/><path class="s5d7qab8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-star" /></template>
