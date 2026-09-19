<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7sak3bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="d7sak3bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:instagram" /></template>
