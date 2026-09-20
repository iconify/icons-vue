<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/eel-4gt1b.css';
import '../../css/a/ap3xz1bbt.css';
import '../../css/e/evg2pjbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="eel-4gt1b"/><path class="ap3xz1bbt"/><path class="evg2pjbkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-with-files-linear" /></template>
