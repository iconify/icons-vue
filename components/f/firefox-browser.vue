<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb88n8bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gb88n8bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:firefox-browser" /></template>
