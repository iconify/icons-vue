<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq0jm3byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jq0jm3byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:keyframe-align-vertical" /></template>
