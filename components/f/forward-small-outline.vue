<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp4s3mbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yp4s3mbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:forward-small-outline" /></template>
