<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3-0fuwea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s3-0fuwea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:globe-favorite" /></template>
