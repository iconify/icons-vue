<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckhg4cclh.css';
import '../../css/l/l6od3hn3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":465,"height":512};
const content = `<path class="ckhg4cclh"/><path class="l6od3hn3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:finder" /></template>
