<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqme3kbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":4.5,"height":4.5,"left":-2,"top":-2};
const content = `<path class="uqme3kbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:lean" /></template>
