<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s80w6w7wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s80w6w7wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-merge-line" /></template>
