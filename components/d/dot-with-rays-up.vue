<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc6a_rusm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jc6a_rusm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dot-with-rays-up" /></template>
