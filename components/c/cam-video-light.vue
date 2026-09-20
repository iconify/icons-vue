<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5k4mmokm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u5k4mmokm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:cam-video-light" /></template>
