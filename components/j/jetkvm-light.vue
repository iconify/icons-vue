<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxc2s3uyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wxc2s3uyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jetkvm-light" /></template>
