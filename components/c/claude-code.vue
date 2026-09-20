<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0h5-obfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u0h5-obfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:claude-code" /></template>
