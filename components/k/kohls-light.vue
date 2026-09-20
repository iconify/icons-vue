<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqm-erb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yqm-erb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kohls-light" /></template>
