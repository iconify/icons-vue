<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoz6ct8xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="eoz6ct8xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:hexadite-investigation-cancel" /></template>
