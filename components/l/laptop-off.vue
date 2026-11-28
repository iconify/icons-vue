<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7ny2zxxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7ny2zxxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:laptop-off" /></template>
