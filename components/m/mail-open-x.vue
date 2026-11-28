<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm5mdouze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm5mdouze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mail-open-x" /></template>
