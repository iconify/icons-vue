<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sua7z4enf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sua7z4enf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hand-stars" /></template>
