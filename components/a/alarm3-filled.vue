<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czrzz41ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czrzz41ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:alarm3-filled" /></template>
