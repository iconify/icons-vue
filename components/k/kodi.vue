<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anhkdg65z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="anhkdg65z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kodi" /></template>
