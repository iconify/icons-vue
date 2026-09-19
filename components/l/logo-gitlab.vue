<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys7-b_bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ys7-b_bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-gitlab" /></template>
