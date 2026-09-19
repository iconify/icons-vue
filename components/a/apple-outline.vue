<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu6ae2f3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iu6ae2f3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:apple-outline" /></template>
