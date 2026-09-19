<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b67ejim3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="b67ejim3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:d-and-d" /></template>
