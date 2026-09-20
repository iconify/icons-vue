<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npr122_rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="npr122_rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ampersand" /></template>
