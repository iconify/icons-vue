<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7atsbiux.css';
import '../../css/y/yakywwbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d7atsbiux"/><path class="yakywwbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-box-double-stroke-20" /></template>
