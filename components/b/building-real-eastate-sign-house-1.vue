<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knlfp1bfs.css';
import '../../css/n/ngqnexboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="knlfp1bfs"/><path class="ngqnexboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:building-real-eastate-sign-house-1" /></template>
