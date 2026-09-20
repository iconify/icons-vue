<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt0-luxxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt0-luxxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:issue-opened-24" /></template>
