<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr399-bdh.css';
import '../../css/i/in-984b7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="zr399-bdh"/><path class="in-984b7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:briefcase-outline" /></template>
