<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voex5_bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="voex5_bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:jet" /></template>
