<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deg907bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="deg907bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kanboard-light" /></template>
