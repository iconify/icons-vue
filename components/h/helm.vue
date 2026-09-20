<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk02ikb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yk02ikb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:helm" /></template>
