<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5bt6abqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5bt6abqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-off" /></template>
