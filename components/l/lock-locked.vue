<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7srk4lqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="w7srk4lqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:lock-locked" /></template>
