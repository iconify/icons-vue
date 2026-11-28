<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn9-em49e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn9-em49e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:git-branch-check-solid" /></template>
