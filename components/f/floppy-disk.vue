<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evjs23bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="evjs23bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:floppy-disk" /></template>
