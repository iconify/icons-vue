<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlovqj5rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlovqj5rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-type-bold" /></template>
