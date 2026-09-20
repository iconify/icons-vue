<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj9evvb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj9evvb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-alt-1-line" /></template>
