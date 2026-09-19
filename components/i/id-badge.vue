<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpqif2bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fpqif2bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:id-badge" /></template>
