<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7b3i5b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7b3i5b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:flag-triangle-right" /></template>
