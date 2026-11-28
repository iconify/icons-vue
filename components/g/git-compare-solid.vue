<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2uh0acfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2uh0acfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:git-compare-solid" /></template>
