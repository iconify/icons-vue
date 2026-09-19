<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3l-hubpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s3l-hubpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-bluesky" /></template>
