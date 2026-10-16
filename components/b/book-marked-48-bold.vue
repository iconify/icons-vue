<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6wbwjb8t.css';
import '../../css/l/l2frilr8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f6wbwjb8t"/><path class="l2frilr8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:book-marked-48-bold" /></template>
