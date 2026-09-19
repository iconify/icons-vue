<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sia2ghlsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sia2ghlsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:file-search" /></template>
