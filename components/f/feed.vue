<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3_unr4bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s3_unr4bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:feed" /></template>
