<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3tz4sp-n.css';
import '../../css/a/ad2r2ebzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j3tz4sp-n"/><path class="ad2r2ebzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:files-20-bold" /></template>
