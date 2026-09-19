<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzgtxzbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hzgtxzbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chevron-collapse" /></template>
