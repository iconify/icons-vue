<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3j2m0_dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s3j2m0_dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:folder-open-fill-16" /></template>
