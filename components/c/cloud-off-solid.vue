<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s40qgyyak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s40qgyyak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:cloud-off-solid" /></template>
