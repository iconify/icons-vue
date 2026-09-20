<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4bdpbc2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u4bdpbc2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-rar-outline" /></template>
