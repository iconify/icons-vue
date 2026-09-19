<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvxsaw3yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zvxsaw3yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:border-top" /></template>
