<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj0xx1u2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="sj0xx1u2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:creative-commons-share" /></template>
