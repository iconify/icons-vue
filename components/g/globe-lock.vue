<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsqcs4bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsqcs4bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:globe-lock" /></template>
