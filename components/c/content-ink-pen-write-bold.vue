<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spopz0byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spopz0byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:content-ink-pen-write-bold" /></template>
