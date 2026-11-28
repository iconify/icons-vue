<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu3eknr8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu3eknr8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-right-solid" /></template>
