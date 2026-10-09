<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4kacqeqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a4kacqeqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-big-right-48" /></template>
