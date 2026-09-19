<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v18c9fbau.css';
import '../../css/f/f_vjhhbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="v18c9fbau"/><path class="f_vjhhbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:at-4x3" /></template>
