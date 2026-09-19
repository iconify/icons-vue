<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn6bq-bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="cn6bq-bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:drink" /></template>
