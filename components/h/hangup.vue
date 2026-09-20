<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf3zqez6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cf3zqez6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:hangup" /></template>
