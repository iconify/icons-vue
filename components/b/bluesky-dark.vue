<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzz0615qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jzz0615qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bluesky-dark" /></template>
