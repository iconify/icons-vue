<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9qim9_gd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9qim9_gd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:erase-filled" /></template>
