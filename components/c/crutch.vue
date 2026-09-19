<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwq7ipbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwq7ipbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:crutch" /></template>
