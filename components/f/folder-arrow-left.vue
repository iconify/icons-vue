<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn7t-fbvk.css';
import '../../css/l/ll5_hob1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn7t-fbvk"/><path clip-rule="evenodd" class="ll5_hob1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-arrow-left" /></template>
