<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um413-_bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um413-_bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-graph" /></template>
