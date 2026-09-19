<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm_wj2bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dm_wj2bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bullhorn" /></template>
