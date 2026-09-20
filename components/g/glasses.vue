<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yisivdb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yisivdb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:glasses" /></template>
