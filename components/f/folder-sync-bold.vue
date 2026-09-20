<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7xnkhmqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u7xnkhmqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-sync-bold" /></template>
