<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1ku2cciy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="o1ku2cciy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:decrease-indent-text-mirrored" /></template>
