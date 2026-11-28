<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfkf-qbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfkf-qbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:git-merge-check" /></template>
