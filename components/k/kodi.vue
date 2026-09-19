<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvhfc9blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvhfc9blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:kodi" /></template>
