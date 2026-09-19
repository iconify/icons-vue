<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdwcnho2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cdwcnho2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:align-center" /></template>
