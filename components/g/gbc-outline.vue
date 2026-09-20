<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byl4ycbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="byl4ycbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:gbc-outline" /></template>
