<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2051z5bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="d2051z5bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:horse-head" /></template>
