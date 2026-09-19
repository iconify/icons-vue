<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjzw_-b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wjzw_-b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:dry-normal-no-heat" /></template>
