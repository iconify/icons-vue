<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzkgl3j1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bzkgl3j1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:apple-watch" /></template>
