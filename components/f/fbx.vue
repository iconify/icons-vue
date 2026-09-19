<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm5lx6bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":388,"height":512};
const content = `<path class="rm5lx6bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:fbx" /></template>
