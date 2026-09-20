<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahdm80qiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahdm80qiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-shield" /></template>
