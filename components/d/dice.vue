<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2js5v_lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="l2js5v_lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:dice" /></template>
