<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roe0f7pai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="roe0f7pai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:git-cherry-pick-commit" /></template>
