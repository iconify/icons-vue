<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp7g_-gpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xp7g_-gpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:instapods" /></template>
