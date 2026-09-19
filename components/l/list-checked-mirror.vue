<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdlftpbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cdlftpbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:list-checked-mirror" /></template>
