<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqf9kac9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yqf9kac9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:file-13" /></template>
