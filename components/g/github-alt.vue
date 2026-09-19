<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8lb625tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="o8lb625tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:github-alt" /></template>
