<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv9d7-4cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":512};
const content = `<path class="nv9d7-4cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:caret-left" /></template>
