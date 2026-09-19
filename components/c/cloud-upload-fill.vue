<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbj2ozb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xbj2ozb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:cloud-upload-fill" /></template>
