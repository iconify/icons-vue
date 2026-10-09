<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_8jrujkz.css';
import '../../css/c/cqfb17bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c_8jrujkz"/><path class="cqfb17bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:briefcase-20-bold" /></template>
