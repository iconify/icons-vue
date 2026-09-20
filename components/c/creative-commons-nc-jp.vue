<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt3rp2b8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yt3rp2b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:creative-commons-nc-jp" /></template>
