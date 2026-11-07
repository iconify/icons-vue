<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvymvrbay.css';
import '../../css/y/yu315fbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dvymvrbay"/><path class="yu315fbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:logout-2-bold" /></template>
