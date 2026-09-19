<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3v2hfb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s3v2hfb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:admin-settings" /></template>
