<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh4o6tbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":700};
const content = `<path class="qh4o6tbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:check" /></template>
