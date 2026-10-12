<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2wsqgbwj.css';
import '../../css/j/jzphsob0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f2wsqgbwj"/><path class="jzphsob0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kick-scooter-20" /></template>
