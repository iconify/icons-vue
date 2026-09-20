<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3u343bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s3u343bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flashpaper" /></template>
