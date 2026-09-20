<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2xbzyw0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u2xbzyw0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cloud-drops" /></template>
