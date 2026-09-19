<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i20o1k74r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="i20o1k74r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:face-meh" /></template>
