<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayp9c8duo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ayp9c8duo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:emby-dark" /></template>
