<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llfxtxbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="llfxtxbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freeresend-light" /></template>
