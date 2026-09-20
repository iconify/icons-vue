<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgsz4nbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wgsz4nbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:corner-up-right-solid" /></template>
