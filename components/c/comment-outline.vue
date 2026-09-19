<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibe_u-t6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="ibe_u-t6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:comment-outline" /></template>
