<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwt6abcmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwt6abcmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:app-window-mac-plus" /></template>
