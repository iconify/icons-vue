<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u30cjache.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u30cjache"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-corrupt" /></template>
