<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0sjwb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx0sjwb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoticon-remove-outline" /></template>
