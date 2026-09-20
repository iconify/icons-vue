<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8r1e1_by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g8r1e1_by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:deviant-art-logo-1-block" /></template>
