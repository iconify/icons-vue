<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llvmp7gcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="llvmp7gcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-align-offset-top-fill" /></template>
