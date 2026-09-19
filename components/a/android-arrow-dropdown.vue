<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt64rj3ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jt64rj3ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-arrow-dropdown" /></template>
