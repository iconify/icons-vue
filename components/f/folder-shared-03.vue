<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k97snyb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k97snyb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-shared-03" /></template>
