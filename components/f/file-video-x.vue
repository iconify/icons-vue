<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s415qeljf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s415qeljf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-video-x" /></template>
