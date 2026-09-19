<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st_46oxgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":16};
const content = `<path class="st_46oxgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:bubbles" /></template>
