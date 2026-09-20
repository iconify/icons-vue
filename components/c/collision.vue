<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-r2a1tbt.css';
import '../../css/x/x3dutabuk.css';
import '../../css/t/t7bcvwf8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="z-r2a1tbt"/><path class="x3dutabuk"/><path class="t7bcvwf8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:collision" /></template>
