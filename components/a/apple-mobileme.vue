<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-n2gk5jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-n2gk5jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:apple-mobileme" /></template>
