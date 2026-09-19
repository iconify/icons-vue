<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp_xnxhpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jp_xnxhpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-arrow-dropleft-circle" /></template>
