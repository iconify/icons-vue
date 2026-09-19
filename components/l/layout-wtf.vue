<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsmn988cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jsmn988cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:layout-wtf" /></template>
