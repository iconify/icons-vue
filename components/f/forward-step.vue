<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekj6dzbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="ekj6dzbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:forward-step" /></template>
