<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9s903bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="f9s903bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:jar" /></template>
