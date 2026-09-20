<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt-1lebpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wt-1lebpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:frosty" /></template>
