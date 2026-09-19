<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7p-s6dcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="z7p-s6dcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-pen" /></template>
