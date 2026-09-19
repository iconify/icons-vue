<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yju4lmbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yju4lmbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call-disabled" /></template>
