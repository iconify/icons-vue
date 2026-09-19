<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnqn2zbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cnqn2zbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:key" /></template>
