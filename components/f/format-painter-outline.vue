<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3qz6_b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s3qz6_b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:format-painter-outline" /></template>
