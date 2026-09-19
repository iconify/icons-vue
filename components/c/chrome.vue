<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls2l6cbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ls2l6cbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:chrome" /></template>
