<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecy_mvlqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="ecy_mvlqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:assignment" /></template>
