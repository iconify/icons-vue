<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkira4mse.css';
import '../../css/d/d8zayxbdq.css';
import '../../css/q/q9gdl6bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lkira4mse"/><path class="d8zayxbdq"/><path class="q9gdl6bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:external-link-20-bold" /></template>
