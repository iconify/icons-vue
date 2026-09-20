<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo1-5g48y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zo1-5g48y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:glasses-bold" /></template>
