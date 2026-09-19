<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roar_qb4z.css';
import '../../css/w/wubo0t6my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="roar_qb4z"/><path class="wubo0t6my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-wxt" /></template>
