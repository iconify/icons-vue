<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q89-ixbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q89-ixbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:label-outline" /></template>
