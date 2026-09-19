<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i72vq7bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i72vq7bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-git-pull-request" /></template>
