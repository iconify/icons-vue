<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whuxrvbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whuxrvbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-fork-round" /></template>
