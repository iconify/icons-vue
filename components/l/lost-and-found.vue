<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5xdj-mrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5xdj-mrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:lost-and-found" /></template>
