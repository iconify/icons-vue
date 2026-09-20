<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1cm9oozd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="z1cm9oozd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:browser-hash" /></template>
