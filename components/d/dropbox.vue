<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyi2f1bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fyi2f1bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:dropbox" /></template>
