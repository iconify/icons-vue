<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_k72rhzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="z_k72rhzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:c" /></template>
