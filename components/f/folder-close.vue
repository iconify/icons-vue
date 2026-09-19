<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8f4i2m7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="j8f4i2m7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:folder-close" /></template>
