<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwz8omazq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cwz8omazq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:lets-encrypt" /></template>
