<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nanvoiber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nanvoiber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-up-down-stroke-20" /></template>
