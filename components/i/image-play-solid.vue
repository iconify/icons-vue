<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auxxc2gzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auxxc2gzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:image-play-solid" /></template>
