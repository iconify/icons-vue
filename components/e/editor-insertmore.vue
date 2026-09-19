<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik_atsbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ik_atsbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-insertmore" /></template>
