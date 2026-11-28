<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1lh88rxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1lh88rxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:activity" /></template>
