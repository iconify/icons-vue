<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk-j6bz5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mk-j6bz5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:bulleted-list-2-mirrored" /></template>
