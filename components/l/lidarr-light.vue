<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_0bz8nxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d_0bz8nxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lidarr-light" /></template>
