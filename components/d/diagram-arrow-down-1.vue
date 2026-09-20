<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e709i7b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e709i7b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:diagram-arrow-down-1" /></template>
