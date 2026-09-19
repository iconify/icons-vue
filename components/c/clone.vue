<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iokcg5b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="iokcg5b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:clone" /></template>
