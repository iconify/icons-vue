<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u79u2pbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u79u2pbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:data-text-duotone" /></template>
