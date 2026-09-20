<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgolb5zaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgolb5zaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-merge" /></template>
