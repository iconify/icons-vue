<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dax8w86yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dax8w86yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chevron-up-24" /></template>
