<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f13n-ehta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f13n-ehta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:bluetooth" /></template>
