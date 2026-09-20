<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfmcc9boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfmcc9boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:git-branch-line" /></template>
