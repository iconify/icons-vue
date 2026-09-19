<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plwc9ubfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="plwc9ubfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:circle" /></template>
