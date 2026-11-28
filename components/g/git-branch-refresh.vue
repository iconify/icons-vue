<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axu82-ogq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axu82-ogq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:git-branch-refresh" /></template>
