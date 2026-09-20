<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u02shab-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u02shab-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bluesky-line" /></template>
