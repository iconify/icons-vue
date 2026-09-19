<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx-xcdc4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mx-xcdc4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:book-closed-stroke-12" /></template>
