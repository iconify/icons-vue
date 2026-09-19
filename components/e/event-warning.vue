<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gur1qyx5l.css';
import '../../css/q/qag32gbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gur1qyx5l"/><path class="qag32gbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:event-warning" /></template>
