<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwaufjzwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwaufjzwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:cursor-24" /></template>
