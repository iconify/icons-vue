<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppe0v7y3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ppe0v7y3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:iphone-home" /></template>
