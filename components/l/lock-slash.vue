<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9nnki7uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9nnki7uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:lock-slash" /></template>
