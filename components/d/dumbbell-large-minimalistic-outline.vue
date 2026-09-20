<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb1iv7qez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zb1iv7qez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbell-large-minimalistic-outline" /></template>
