<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3qtozs6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x3qtozs6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:last-fm" /></template>
